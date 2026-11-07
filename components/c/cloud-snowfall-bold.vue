<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9eme7ben.css';
import '../../css/b/bruiaybse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9eme7ben"/><path class="bruiaybse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-snowfall-bold" /></template>
