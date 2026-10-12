<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b00pbxr6w.css';
import '../../css/g/gjba8cbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b00pbxr6w"/><path class="gjba8cbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-minus-2-filled" /></template>
