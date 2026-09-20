<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmj--94hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmj--94hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-image-fill" /></template>
