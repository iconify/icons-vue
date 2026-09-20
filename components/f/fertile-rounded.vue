<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1axalbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fertile-rounded" /></template>
<style>
.h1axalbas {
  fill: currentColor;
  d: path("M12.806 4.442q.783.966 1.5 1.975t1.394 2.05l4.008-2.998q.186-.136.404-.161t.434.08t.336.307t.118.42V12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709t-3.51-.709q-1.643-.708-2.859-1.923T3.709 15.51T3 12V6.114q0-.216.118-.418q.119-.202.336-.303q.217-.11.435-.085t.403.161l3.983 2.998q.677-1.04 1.416-2.04q.74-1 1.522-1.966q.154-.184.35-.289T12 4.067t.449.098t.357.277");
}

</style>
