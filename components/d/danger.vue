<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlqqbzuhn.css';
import '../../css/b/b_4q_nb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="mlqqbzuhn"/><path class="b_4q_nb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:danger" /></template>
