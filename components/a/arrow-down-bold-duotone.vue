<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz_lgvb5c.css';
import '../../css/a/adl-4zb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz_lgvb5c"/><path class="adl-4zb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-bold-duotone" /></template>
