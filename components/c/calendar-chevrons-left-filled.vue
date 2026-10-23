<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np4301h5k.css';
import '../../css/j/j8ev3vexx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np4301h5k"/><path class="j8ev3vexx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-chevrons-left-filled" /></template>
