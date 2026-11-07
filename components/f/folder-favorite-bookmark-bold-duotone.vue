<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twg_fi4pi.css';
import '../../css/k/kd5gzltfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twg_fi4pi"/><path class="kd5gzltfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favorite-bookmark-bold-duotone" /></template>
