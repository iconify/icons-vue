<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rus3__a3u.css';
import '../../css/c/cu3aa_zia.css';
import '../../css/y/yb6kx8bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rus3__a3u wm-k"/><path class="cu3aa_zia wm-k"/><path class="wm-a yb6kx8bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:folder-minus" /></template>
