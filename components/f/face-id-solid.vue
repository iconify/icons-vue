<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6tjm_bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u6tjm_bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:face-id-solid" /></template>
