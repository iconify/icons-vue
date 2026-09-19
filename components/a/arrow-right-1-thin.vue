<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etig-9n9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etig-9n9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-1-thin" /></template>
