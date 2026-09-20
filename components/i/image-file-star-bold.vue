<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_pr9ks0t.css';
import '../../css/c/czhl_6b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_pr9ks0t"/><path class="czhl_6b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:image-file-star-bold" /></template>
