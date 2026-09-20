<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilg756wim.css';
import '../../css/l/llov8mbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilg756wim"/><path class="llov8mbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-article-filled" /></template>
