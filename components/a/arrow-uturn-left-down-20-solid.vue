<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijr2znasw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ijr2znasw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-left-down-20-solid" /></template>
