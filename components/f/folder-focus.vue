<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bcqa_q4nr.css';
import '../../css/z/z4-yyfbvs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7VLLbfQH"><g class="ufeehvblu"><path class="bcqa_q4nr"/><path class="z4-yyfbvs"/></g></mask></defs><path mask="url(#SVG7VLLbfQH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:folder-focus" /></template>
