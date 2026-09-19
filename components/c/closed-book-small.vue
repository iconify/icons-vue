<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixkerdb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ixkerdb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:closed-book-small" /></template>
