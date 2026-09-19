<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnqri_byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fnqri_byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingeight" /></template>
