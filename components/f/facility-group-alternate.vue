<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbilk4ndb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbilk4ndb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:facility-group-alternate" /></template>
