<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c54sfd9tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c54sfd9tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:chess-rook" /></template>
