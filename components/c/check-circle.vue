<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smbnb7bef.css';
import '../../css/p/pln5qlbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smbnb7bef"/><path class="pln5qlbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-circle" /></template>
