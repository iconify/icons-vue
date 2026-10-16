<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo0xevpbl.css';
import '../../css/b/b9o66unef.css';
import '../../css/z/zw7micchl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eo0xevpbl"/><path class="b9o66unef"/><path class="zw7micchl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-balancing-48-bold" /></template>
