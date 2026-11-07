<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoshjbpvd.css';
import '../../css/b/bt37pjbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoshjbpvd"/><path class="bt37pjbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-bold-duotone" /></template>
