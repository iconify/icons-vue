<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor-usn7v.css';
import '../../css/n/nu3gegi7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jor-usn7v"/><path class="nu3gegi7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-ul-square" /></template>
