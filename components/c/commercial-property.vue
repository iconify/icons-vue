<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_f_sbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:commercial-property" /></template>
<style>
.ru_f_sbvb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.329 7.665l2-4q.047-.094.117-.171t.16-.132t.189-.083Q4.896 3.25 5 3.25h14q.104 0 .205.029q.1.028.189.083t.16.132q.07.077.117.171l2 4q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18q-.066.033-.137.052q-.071.02-.145.025t-.147-.004t-.143-.032t-.134-.06t-.12-.085t-.101-.107t-.079-.125L18.536 4.75H5.464L3.671 8.335q-.033.066-.079.125q-.045.058-.101.107q-.055.048-.12.085q-.064.036-.134.06q-.07.023-.143.032t-.147.004t-.145-.025t-.137-.052q-.134-.067-.232-.18q-.097-.112-.145-.254q-.047-.141-.036-.29q.01-.149.077-.282m4.296-.415h10.75q3.375 0 3.375 3.375v7.25q0 3.375-3.375 3.375H14q.932 0 1.591-.659T16.25 19v-5q0-.932-.659-1.591T14 11.75h-4q-2.25 0-2.25 2.25v5q0 2.25 2.25 2.25H6.625q-3.375 0-3.375-3.375v-7.25q0-3.375 3.375-3.375");
}

</style>
