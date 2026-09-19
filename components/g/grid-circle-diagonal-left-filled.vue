<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5evaxbui.css';
import '../../css/b/bhbvqjyxk.css';
import '../../css/k/kr2jicboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5evaxbui"/><rect class="bhbvqjyxk"/><rect class="kr2jicboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-diagonal-left-filled" /></template>
