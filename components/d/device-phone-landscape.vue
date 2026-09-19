<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh_6rj7_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oh_6rj7_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:device-phone-landscape" /></template>
