<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbo0gbb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="kbo0gbb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fuel-11" /></template>
