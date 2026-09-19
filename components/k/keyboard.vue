<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/d/d9n_kpbfh.css';
import '../../css/n/n08b62aoj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQPlCdath"><g class="ft5dv1b6b"><path class="arj7difgh"/><path clip-rule="evenodd" class="d9n_kpbfh"/><path class="n08b62aoj"/></g></mask></defs><path mask="url(#SVGQPlCdath)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:keyboard" /></template>
