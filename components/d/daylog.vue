<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvvxebbmy.css';
import '../../css/x/x9osqmkwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvvxebbmy"/><path class="x9osqmkwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daylog" /></template>
