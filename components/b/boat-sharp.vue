<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb3g90wjy.css';
import '../../css/s/snfmd8b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb3g90wjy"/><path class="snfmd8b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:boat-sharp" /></template>
