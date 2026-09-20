<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lix1ev9xm.css';
import '../../css/j/jjbqhzpum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lix1ev9xm"/><path class="jjbqhzpum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-none-fill" /></template>
