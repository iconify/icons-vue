<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ii7tboz.css';
import '../../css/e/elo702b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z0ii7tboz"/><path class="elo702b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cobalt-20" /></template>
