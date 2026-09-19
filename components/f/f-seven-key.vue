<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/g/gtcu9q4ff.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLlWc9dKc"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="gtcu9q4ff"/></g></mask></defs><path mask="url(#SVGLlWc9dKc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:f-seven-key" /></template>
