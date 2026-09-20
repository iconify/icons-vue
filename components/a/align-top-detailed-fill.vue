<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzg60ubxn.css';
import '../../css/z/z4470fb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzg60ubxn"/><path clip-rule="evenodd" class="z4470fb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-top-detailed-fill" /></template>
