<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flfbxac5m.css';
import '../../css/u/u7znvqguw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flfbxac5m"/><path class="u7znvqguw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coffee-beans-filled" /></template>
