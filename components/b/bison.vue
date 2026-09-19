<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac6_keb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac6_keb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bison" /></template>
