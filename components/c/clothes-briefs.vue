<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en2ec-blp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzzFfQcsj"><path class="en2ec-blp"/></mask></defs><path mask="url(#SVGzzFfQcsj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:clothes-briefs" /></template>
