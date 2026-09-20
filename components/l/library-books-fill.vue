<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgk9gw7ra.css';
import '../../css/j/jjbqhzpum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgk9gw7ra"/><path class="jjbqhzpum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:library-books-fill" /></template>
