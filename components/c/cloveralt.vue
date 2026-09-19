<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g--9au63c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g--9au63c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloveralt" /></template>
