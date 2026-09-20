<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvi257b1u.css';
import '../../css/k/kyxjq5b8z.css';
import '../../css/p/p_1scj-cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvi257b1u"/><path class="kyxjq5b8z"/><path class="p_1scj-cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:cog" /></template>
