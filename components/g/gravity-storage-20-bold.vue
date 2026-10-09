<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ahsnbld.css';
import '../../css/w/wc5gufbvx.css';
import '../../css/i/itu8fbbds.css';
import '../../css/v/vjij33b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-ahsnbld"/><path class="wc5gufbvx"/><path class="itu8fbbds"/><path class="vjij33b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gravity-storage-20-bold" /></template>
