<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzj-69x7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzj-69x7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-fill" /></template>
