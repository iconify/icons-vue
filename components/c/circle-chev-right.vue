<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi9qgerqe.css';
import '../../css/t/t7bnoab5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi9qgerqe"/><path class="t7bnoab5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-chev-right" /></template>
