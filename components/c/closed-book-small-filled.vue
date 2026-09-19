<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nutj0lbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nutj0lbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:closed-book-small-filled" /></template>
