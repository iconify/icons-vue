<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib8412b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ib8412b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:email-fill-26" /></template>
