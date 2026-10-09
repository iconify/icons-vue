<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rio2np7vm.css';
import '../../css/e/e2weyn4xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rio2np7vm"/><path class="e2weyn4xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-20" /></template>
