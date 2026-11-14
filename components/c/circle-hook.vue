<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-qj06twn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circle-hook" /></template>
<style>
.c-qj06twn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.25Q5.25 2.25 5.25 5q0 2.345 2 2.69V15q.034 2.587 1.981 4.276q1.946 1.69 4.502 1.361t4.012-2.456t.836-4.629q-.619-2.502-2.899-3.704t-4.694-.301q-.1.038-.186.101q-.085.064-.15.149t-.102.185q-.039.099-.047.206l-.25 3q-.007.073.002.147q.008.073.031.143q.022.071.058.135t.083.121t.106.103t.123.08q.066.034.137.054t.145.026t.147-.002t.143-.031t.135-.058t.121-.083t.103-.106t.08-.123q.034-.066.054-.137t.026-.145l.209-2.501q1.551-.414 3.026.364q1.685.888 2.143 2.737t-.618 3.422t-2.965 1.815t-3.328-1.005Q8.775 16.895 8.75 15V7.69q2-.345 2-2.69q0-2.75-2.75-2.75");
}

</style>
