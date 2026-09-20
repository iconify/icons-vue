<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shbgs2bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shbgs2bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:double-bookmark-remix" /></template>
