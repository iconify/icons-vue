<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pltnho7ea.css';
import '../../css/v/voyj7e3gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pltnho7ea"/><path class="voyj7e3gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-top-left-16" /></template>
