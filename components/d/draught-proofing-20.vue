<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_fvlabzg.css';
import '../../css/n/nou07ac-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z_fvlabzg"/><path class="nou07ac-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:draught-proofing-20" /></template>
