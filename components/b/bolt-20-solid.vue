<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6jcmg63q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v6jcmg63q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bolt-20-solid" /></template>
