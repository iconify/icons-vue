<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc7aclrmb.css';
import '../../css/f/f4xb95eqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc7aclrmb"/><path clip-rule="evenodd" class="f4xb95eqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-unlock-fill" /></template>
