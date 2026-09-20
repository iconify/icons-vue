<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbtlfqbcg.css';
import '../../css/q/qoc3rw04c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kbtlfqbcg"/><path class="qoc3rw04c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-laboratory" /></template>
