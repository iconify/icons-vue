<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj2430bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jj2430bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:facebook-small" /></template>
