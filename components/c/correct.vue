<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-9rzj9m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6XSMvrWP"><path clip-rule="evenodd" class="lh-9rzj9m"/></mask></defs><path mask="url(#SVG6XSMvrWP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:correct" /></template>
