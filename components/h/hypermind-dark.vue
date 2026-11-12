<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa1q5gb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aa1q5gb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hypermind-dark" /></template>
