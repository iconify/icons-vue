<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tweml3g7s.css';
import '../../css/s/sk9-dtbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tweml3g7s"/><path clip-rule="evenodd" class="sk9-dtbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:info-32" /></template>
