<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhq7kcjjd.css';
import '../../css/c/ck8dpqbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uhq7kcjjd"/><path clip-rule="evenodd" class="ck8dpqbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:info-12" /></template>
