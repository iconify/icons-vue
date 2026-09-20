<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdp245_wj.css';
import '../../css/t/ttyer50st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="hdp245_wj"/><path class="ttyer50st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:clone" /></template>
