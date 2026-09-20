<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egq4ghbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egq4ghbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cardano" /></template>
