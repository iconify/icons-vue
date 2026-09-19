<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugkyat6-v.css';
import '../../css/a/a1iy-fbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ugkyat6-v"/><path clip-rule="evenodd" class="a1iy-fbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:lock-filled" /></template>
