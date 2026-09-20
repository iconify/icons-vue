<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj4rqzjdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj4rqzjdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:japanairlines" /></template>
