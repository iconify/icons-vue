<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glj_s2bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="glj_s2bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:control-forward" /></template>
