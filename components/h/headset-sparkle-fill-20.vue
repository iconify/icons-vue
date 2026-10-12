<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_le4c4m.css';
import '../../css/k/k0kzc1obh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sl_le4c4m"/><path class="k0kzc1obh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-sparkle-fill-20" /></template>
