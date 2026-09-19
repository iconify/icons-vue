<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor-usn7v.css';
import '../../css/t/t7w3f5b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b jor-usn7v"/><path class="b t7w3f5b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:background-color-fill" /></template>
