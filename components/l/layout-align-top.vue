<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-nva6oky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-nva6oky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layout-align-top" /></template>
