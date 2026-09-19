<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl04e0ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl04e0ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-edit-alt-filled" /></template>
