<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjk5al0qp.css';
import '../../css/u/u3fekhbnn.css';
import '../../css/h/hvm7gjbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjk5al0qp"/><path class="u3fekhbnn"/><path class="hvm7gjbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-bold-duotone" /></template>
