<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezau3nrei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezau3nrei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alien-filled" /></template>
