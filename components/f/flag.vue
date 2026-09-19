<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm995dbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jm995dbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:flag" /></template>
