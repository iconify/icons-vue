<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e41i3kafz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e41i3kafz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up-16-solid" /></template>
