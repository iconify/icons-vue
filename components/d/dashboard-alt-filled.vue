<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdmx5bchb.css';
import '../../css/b/bsi-fab-z.css';
import '../../css/z/z_t34acqg.css';
import '../../css/k/kyxodwdpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="tdmx5bchb"/><rect class="bsi-fab-z"/><rect class="z_t34acqg"/><rect class="kyxodwdpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dashboard-alt-filled" /></template>
