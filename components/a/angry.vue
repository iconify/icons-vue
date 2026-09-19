<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvra6zb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mvra6zb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:angry" /></template>
