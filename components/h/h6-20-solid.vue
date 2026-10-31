<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf70tib7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kf70tib7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h6-20-solid" /></template>
