<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu2vv7b8r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmIvModQC"><path class="lu2vv7b8r"/></mask></defs><path mask="url(#SVGmIvModQC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:easy" /></template>
