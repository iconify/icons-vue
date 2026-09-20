<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8xm9jn1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8xm9jn1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:asterisk-duotone" /></template>
