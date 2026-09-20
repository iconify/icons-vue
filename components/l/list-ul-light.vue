<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71zbv5lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k71zbv5lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:list-ul-light" /></template>
