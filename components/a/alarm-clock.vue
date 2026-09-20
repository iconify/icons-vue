<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlnc8j4gt.css';
import '../../css/w/w-f7zlbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hlnc8j4gt"/><path class="w-f7zlbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:alarm-clock" /></template>
