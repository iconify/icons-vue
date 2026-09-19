<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-mg1bbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p-mg1bbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-grin-tongue" /></template>
