<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zee_p2c7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zee_p2c7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:education-filled" /></template>
