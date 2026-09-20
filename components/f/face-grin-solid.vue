<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlrhk_-_t.css';
import '../../css/b/blghhjben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlrhk_-_t"/><path class="blghhjben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-grin-solid" /></template>
