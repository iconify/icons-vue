<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtpw-r91t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtpw-r91t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-alt-02" /></template>
