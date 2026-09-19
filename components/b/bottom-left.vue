<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtjdqybjn.css';
import '../../css/n/nhs-d-bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xtjdqybjn"/><path class="nhs-d-bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:bottom-left" /></template>
