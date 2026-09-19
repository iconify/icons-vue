<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlqv5wloy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tlqv5wloy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:generate-file-filled" /></template>
