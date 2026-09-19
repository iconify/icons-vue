<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9xybybew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y9xybybew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex" /></template>
