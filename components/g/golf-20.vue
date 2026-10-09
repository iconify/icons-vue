<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md4nzgbup.css';
import '../../css/e/e41hepbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="md4nzgbup"/><path class="e41hepbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:golf-20" /></template>
