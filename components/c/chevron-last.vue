<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihrukyb8a.css';
import '../../css/b/bio4c781y.css';
import '../../css/u/u9zxaeb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihrukyb8a wm-k"/><path class="bio4c781y wm-k"/><path class="u9zxaeb-g wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevron-last" /></template>
