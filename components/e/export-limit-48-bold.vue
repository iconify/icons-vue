<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl_of99ub.css';
import '../../css/a/a81jttbcu.css';
import '../../css/l/lh_ofmq9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tl_of99ub"/><path class="a81jttbcu"/><path class="lh_ofmq9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:export-limit-48-bold" /></template>
