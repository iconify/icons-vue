<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j32zss-kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j32zss-kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heading-solid" /></template>
