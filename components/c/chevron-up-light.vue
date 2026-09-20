<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v68lmw7lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v68lmw7lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-up-light" /></template>
