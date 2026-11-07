<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2u1s5b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2u1s5b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cc-solid" /></template>
