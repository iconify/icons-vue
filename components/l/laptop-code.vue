<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7wp6fi0u.css';
import '../../css/x/xe2sc8z7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7wp6fi0u"/><path class="xe2sc8z7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:laptop-code" /></template>
