<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pw_3lzbwf.css';
import '../../css/t/tw37qebcv.css';
import '../../css/g/g23-atezb.css';
import '../../css/z/zevwslsun.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpHBXb4JM"><g class="ft5dv1b6b"><path class="pw_3lzbwf"/><path class="tw37qebcv"/><path class="g23-atezb"/><path class="zevwslsun"/></g></mask></defs><path mask="url(#SVGpHBXb4JM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-display-one" /></template>
