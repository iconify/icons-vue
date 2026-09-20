<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilxn7f33c.css';
import '../../css/e/e-qkt480u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ilxn7f33c"/><path clip-rule="evenodd" class="e-qkt480u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:layout-screen-vertical-16" /></template>
