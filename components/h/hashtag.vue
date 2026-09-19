<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if3utg6ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="if3utg6ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:hashtag" /></template>
