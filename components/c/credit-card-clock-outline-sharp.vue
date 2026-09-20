<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_rbhabka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-clock-outline-sharp" /></template>
<style>
.y_rbhabka {
  fill: currentColor;
  d: path("m19.406 19.26l.546-.546l-1.894-1.895v-2.742h-.77v3.065zm-1.727 2.029q-1.812 0-3.072-1.248q-1.26-1.249-1.26-3.06t1.26-3.07t3.072-1.257q1.806 0 3.054 1.26t1.248 3.067t-1.248 3.057t-3.054 1.25M4 18v-7.692v.479V6zm0-9.192h16V6H4zM11.267 19H3V5h18v6.287q-.76-.472-1.634-.726q-.874-.253-1.831-.253q-.868 0-1.669.23q-.8.23-1.481.654H4V18h7.014q.055.275.109.516q.054.24.144.484");
}

</style>
