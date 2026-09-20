<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge94l3j4u.css';
import '../../css/p/p1-wg6b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ge94l3j4u"/><path clip-rule="evenodd" class="p1-wg6b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:grid-16" /></template>
