<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcpy7abwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lcpy7abwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex-tracker" /></template>
