<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9nnej6xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9nnej6xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-04" /></template>
