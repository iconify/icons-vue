<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql8p6zoco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql8p6zoco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-navbar-collapse-filled" /></template>
