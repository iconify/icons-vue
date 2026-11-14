<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jej3jqb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crochet-hook" /></template>
<style>
.jej3jqb7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.445 15.056q0-.639-.279-1.162L19.53 5.53q.201-.201.385-.109q.169.085.1.432q-.015.072-.015.146t.014.147q.015.072.043.14t.069.13q.041.061.093.114q.052.052.114.093q.061.041.129.07q.068.028.141.042t.146.015t.147-.014q.072-.015.14-.043t.13-.069t.114-.093t.093-.114t.07-.129q.028-.068.042-.141q.295-1.471-.9-2.068q-1.15-.575-2.115.391l-8.364 8.364q-.523-.279-1.162-.279q-1.035 0-1.767.733l-3.889 3.889q-.733.732-.733 1.768q0 1.035.733 1.767q.732.733 1.768.733q1.035 0 1.767-.733l3.889-3.889q.733-.732.733-1.767m2.55-.061Q12.75 16.24 12.75 18t1.245 3.005T17 22.25q.79 0 1.475-.25q.087.002.172-.015q.132-.026.246-.096t.197-.176q.488-.281.915-.708Q21.25 19.76 21.25 18t-1.245-3.005T17 13.75t-3.005 1.245");
}

</style>
