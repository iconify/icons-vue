<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7kue2rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lu7kue2rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-up-bracket" /></template>
