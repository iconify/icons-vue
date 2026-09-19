<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsqwqxj7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsqwqxj7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-left" /></template>
