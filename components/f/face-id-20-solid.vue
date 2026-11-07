<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4lf7envc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c4lf7envc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-id-20-solid" /></template>
