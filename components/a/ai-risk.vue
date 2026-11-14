<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbzllrbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-risk" /></template>
<style>
.dbzllrbel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.534 20H7.422q-.085 0-.17-.005q-.084-.006-.169-.017q-.084-.011-.167-.027q-.084-.017-.166-.038q-.082-.022-.162-.049q-.081-.027-.16-.059q-.078-.032-.155-.069q-.076-.038-.15-.08t-.145-.088t-.138-.098t-.133-.107q-.064-.055-.124-.115q-.061-.059-.118-.123q-.056-.063-.109-.13q-.052-.067-.1-.137t-.092-.143t-.082-.149q-.038-.075-.072-.153t-.062-.158t-.051-.162t-.042-.165q-.017-.083-.03-.167t-.02-.169t-.008-.169t.002-.17t.014-.169t.024-.168t.035-.166t.046-.164t.056-.16t.067-.156q.035-.077.076-.152l4.579-8.393q.084-.154.189-.296q.104-.142.226-.269q.122-.126.26-.236t.289-.199t.314-.158t.331-.116q.17-.046.345-.07q.174-.023.35-.023t.35.023q.175.024.345.07t.331.116q.162.069.314.158q.151.09.289.199t.26.236t.226.269t.189.296l2.347 4.301M12 8.5V13m0 3h.01M18 14.5q.5 3 3.5 3.5q-3 .5-3.5 3.5q-.5-3-3.5-3.5q3-.5 3.5-3.5");
}

</style>
